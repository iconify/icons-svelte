<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5e5623cj.css';
import '../../css/f/fjjuhwb3o.css';
import '../../css/k/k17j4pb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b5e5623cj"/><path class="fjjuhwb3o"/><path class="k17j4pb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-cash-payment-coin" {...props}></Icon>
