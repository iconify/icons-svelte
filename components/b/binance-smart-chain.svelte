<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_re0ro9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_re0ro9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:binance-smart-chain" {...props}></Icon>
