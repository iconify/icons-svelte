<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1538reyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f1538reyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:money-payments-accounting-bill-money-1" {...props}></Icon>
