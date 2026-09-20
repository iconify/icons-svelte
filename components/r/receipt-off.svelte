<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh8_-yihl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh8_-yihl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-off" {...props}></Icon>
