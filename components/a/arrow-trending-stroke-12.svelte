<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qku5pfb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qku5pfb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-trending-stroke-12" {...props}></Icon>
