<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzyoafbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzyoafbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-cash-search" {...props}></Icon>
