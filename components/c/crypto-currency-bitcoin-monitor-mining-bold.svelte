<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsf19acra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsf19acra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:crypto-currency-bitcoin-monitor-mining-bold" {...props}></Icon>
