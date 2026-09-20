<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxxx8-_sp.css';
import '../../css/f/fvb7ntb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxxx8-_sp"/><path class="fvb7ntb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-credit-card-mastercard" {...props}></Icon>
