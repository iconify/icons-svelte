<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bceb90b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bceb90b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:binance-usd-busd-line" {...props}></Icon>
