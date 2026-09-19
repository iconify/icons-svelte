<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rurotwblm.css';
import '../../css/w/w59hr4b9z.css';
import '../../css/f/f4c56ub5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rurotwblm"/><path class="w59hr4b9z"/><path class="f4c56ub5v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bus-duo" {...props}></Icon>
