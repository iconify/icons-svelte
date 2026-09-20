<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6u9q2rkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6u9q2rkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-currency-euro-dollar-exchange" {...props}></Icon>
