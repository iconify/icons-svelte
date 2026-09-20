<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zycxy2t0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zycxy2t0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt" {...props}></Icon>
