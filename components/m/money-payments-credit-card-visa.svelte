<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxxx8-_sp.css';
import '../../css/h/hp5jyobim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxxx8-_sp"/><path class="hp5jyobim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-credit-card-visa" {...props}></Icon>
