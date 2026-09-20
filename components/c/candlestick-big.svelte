<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w48k0s7hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w48k0s7hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:candlestick-big" {...props}></Icon>
