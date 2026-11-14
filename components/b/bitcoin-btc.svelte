<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcvbmhb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcvbmhb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bitcoin-btc" {...props}></Icon>
