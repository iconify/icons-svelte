<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwrxzmuix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwrxzmuix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:map-pin-home" {...props}></Icon>
