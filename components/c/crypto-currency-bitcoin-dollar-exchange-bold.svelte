<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft95ixbdo.css';
import '../../css/h/hw6ek8bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft95ixbdo"/><path class="hw6ek8bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:crypto-currency-bitcoin-dollar-exchange-bold" {...props}></Icon>
