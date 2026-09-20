<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yspu1txce.css';
import '../../css/e/em8icc8zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary yspu1txce"/><path class="em8icc8zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-packetbeat" {...props}></Icon>
