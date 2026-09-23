<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xozg72bpw.css';
import '../../css/r/r7xk8o29f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xozg72bpw"/><path vector-effect="non-scaling-stroke" class="r7xk8o29f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:justify-space-evenly" {...props}></Icon>
