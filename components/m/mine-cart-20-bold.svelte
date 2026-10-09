<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocf3ptrqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ocf3ptrqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-cart-20-bold" {...props}></Icon>
