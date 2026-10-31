<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_i7jf3cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_i7jf3cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-candlestick-round" {...props}></Icon>
