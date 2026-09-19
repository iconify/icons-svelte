<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dccl6cslv.css';
import '../../css/a/a0a43bbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="dccl6cslv"/><path class="a0a43bbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:gear" {...props}></Icon>
