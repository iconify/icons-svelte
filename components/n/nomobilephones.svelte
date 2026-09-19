<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egi7t0uie.css';
import '../../css/v/vnh2invat.css';
import '../../css/i/ixbj2wbiv.css';
import '../../css/a/a23i8nphm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egi7t0uie"/><path class="vnh2invat"/><path class="ixbj2wbiv"/><path class="a23i8nphm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:nomobilephones" {...props}></Icon>
