<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdptxfbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdptxfbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-horizontal-align-right" {...props}></Icon>
