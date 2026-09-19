<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkglbdcce.css';
import '../../css/t/ts0tfxa1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kkglbdcce"/><path class="ts0tfxa1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-at" {...props}></Icon>
