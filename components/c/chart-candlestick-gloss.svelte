<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1e1tuxsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1e1tuxsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-candlestick-gloss" {...props}></Icon>
