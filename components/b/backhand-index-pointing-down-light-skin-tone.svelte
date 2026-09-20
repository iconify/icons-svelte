<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6_a4eb-x.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/l/l9wgslc9t.css';
import '../../css/z/zp34hmbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="c6_a4eb-x"/><g class="ij2x_72vy"><path class="l9wgslc9t"/><path class="zp34hmbbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:backhand-index-pointing-down-light-skin-tone" {...props}></Icon>
