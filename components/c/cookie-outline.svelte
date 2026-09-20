<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_lo8e9qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_lo8e9qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cookie-outline" {...props}></Icon>
