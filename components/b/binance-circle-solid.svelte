<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynf1kozfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ynf1kozfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:binance-circle-solid" {...props}></Icon>
