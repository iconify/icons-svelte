<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naykjyb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="naykjyb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:flask" {...props}></Icon>
