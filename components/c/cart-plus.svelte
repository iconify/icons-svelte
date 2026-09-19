<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3jftogaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="i3jftogaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cart-plus" {...props}></Icon>
