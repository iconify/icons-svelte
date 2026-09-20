<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl401gbue.css';
import '../../css/x/xjfts2dhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl401gbue"/><path class="xjfts2dhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cash-payment-bill-bold" {...props}></Icon>
