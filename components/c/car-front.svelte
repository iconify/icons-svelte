<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkki8g2_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkki8g2_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:car-front" {...props}></Icon>
