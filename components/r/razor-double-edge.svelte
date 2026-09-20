<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy4rdnbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy4rdnbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:razor-double-edge" {...props}></Icon>
