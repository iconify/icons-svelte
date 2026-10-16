<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4s-jblr.css';
import '../../css/q/qrg4uebsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="qrg4uebsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-tax-48-bold" {...props}></Icon>
