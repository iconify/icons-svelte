<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgw_5gsvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgw_5gsvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-send" {...props}></Icon>
