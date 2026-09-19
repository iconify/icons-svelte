<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhm26nblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhm26nblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cart-plus-fill" {...props}></Icon>
