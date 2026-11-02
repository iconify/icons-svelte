<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qei0r4z2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qei0r4z2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:binance-usd-busd-fill" {...props}></Icon>
