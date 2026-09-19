<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txri1yb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="txri1yb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:product-categories" {...props}></Icon>
