<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpm12ebsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpm12ebsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:binance-coin-bnb-fill" {...props}></Icon>
