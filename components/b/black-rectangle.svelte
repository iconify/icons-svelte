<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5kdsjbsk.css';
import '../../css/w/wl2vi-wfs.css';
import '../../css/p/ph-mjcb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="u5kdsjbsk"/><path class="wl2vi-wfs"/><path class="ph-mjcb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-rectangle" {...props}></Icon>
