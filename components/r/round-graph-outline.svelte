<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0sedyn1y.css';
import '../../css/x/x0zzi0bor.css';
import '../../css/n/nh75w0b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0sedyn1y"/><path class="x0zzi0bor"/><path class="nh75w0b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-graph-outline" {...props}></Icon>
