<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tleo8_bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tleo8_bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:dial-finger-1-bold" {...props}></Icon>
