<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkqp70bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkqp70bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:music-line" {...props}></Icon>
