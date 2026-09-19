<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgv2o9bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zgv2o9bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:five-tile-grid" {...props}></Icon>
