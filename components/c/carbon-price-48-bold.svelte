<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5t0sbxt.css';
import '../../css/u/u2hgkfb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5t0sbxt"/><path class="u2hgkfb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-price-48-bold" {...props}></Icon>
