<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrc2k_n9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jrc2k_n9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gitbook" {...props}></Icon>
