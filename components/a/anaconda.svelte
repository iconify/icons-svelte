<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo27_sxlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yo27_sxlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:anaconda" {...props}></Icon>
