<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz5nhebgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zz5nhebgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-cart-20" {...props}></Icon>
