<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz1m-7h_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1m-7h_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:binance-coin-bnb-line" {...props}></Icon>
