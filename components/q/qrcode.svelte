<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3sp0ypbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3sp0ypbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:qrcode" {...props}></Icon>
