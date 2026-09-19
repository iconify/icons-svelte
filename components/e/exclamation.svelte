<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/z/zcicxlhte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="zcicxlhte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:exclamation" {...props}></Icon>
