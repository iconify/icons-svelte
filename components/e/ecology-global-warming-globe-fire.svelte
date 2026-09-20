<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd3xeabnc.css';
import '../../css/x/xdekdlbik.css';
import '../../css/c/c16sh3j5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kd3xeabnc"/><path class="xdekdlbik"/><path class="c16sh3j5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-global-warming-globe-fire" {...props}></Icon>
