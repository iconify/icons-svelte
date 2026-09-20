<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfj95vbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfj95vbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:done" {...props}></Icon>
