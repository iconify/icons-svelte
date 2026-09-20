<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azafrgb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="azafrgb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:money-cashier-tag-codes-tags-tag-product-label" {...props}></Icon>
