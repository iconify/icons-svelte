<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qitm67bso.css';
import '../../css/v/vwcipgbuu.css';
import '../../css/e/en7xt8pxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qitm67bso"/><path class="vwcipgbuu"/><path class="en7xt8pxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-4k" {...props}></Icon>
