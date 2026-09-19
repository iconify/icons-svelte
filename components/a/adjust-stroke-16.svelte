<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/z/z4wa8q0gl.css';
import '../../css/r/r1dzezbll.css';
import '../../css/w/w9lxmxb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="z4wa8q0gl"/><circle class="r1dzezbll"/><path class="w9lxmxb1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:adjust-stroke-16" {...props}></Icon>
