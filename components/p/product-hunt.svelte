<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch3f4qbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ch3f4qbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:product-hunt" {...props}></Icon>
