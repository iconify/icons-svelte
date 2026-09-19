<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrwkr7w4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrwkr7w4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-download" {...props}></Icon>
