<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7w-e1i8e.css';
import '../../css/k/khuf8xa_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v7w-e1i8e"/><path class="khuf8xa_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-wallet-money" {...props}></Icon>
