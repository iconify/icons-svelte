<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmsf81b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qmsf81b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-bag-money" {...props}></Icon>
