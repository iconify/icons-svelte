<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-31_hbov.css';
import '../../css/r/rw2_921jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g-31_hbov"/><path class="rw2_921jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:binoculars-48" {...props}></Icon>
