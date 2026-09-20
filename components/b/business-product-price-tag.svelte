<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bplaobd3f.css';
import '../../css/x/x7qp0hbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bplaobd3f"/><path class="x7qp0hbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-product-price-tag" {...props}></Icon>
