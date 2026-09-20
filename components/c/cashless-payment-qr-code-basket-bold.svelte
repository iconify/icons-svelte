<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fco4h-r_s.css';
import '../../css/l/ljjk5bimi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fco4h-r_s"/><path class="ljjk5bimi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cashless-payment-qr-code-basket-bold" {...props}></Icon>
