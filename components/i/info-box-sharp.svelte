<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux4ezo1do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux4ezo1do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:info-box-sharp" {...props}></Icon>
