<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg7wprbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg7wprbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:binance-coin-bnb-line" {...props}></Icon>
