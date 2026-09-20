<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzdkbtbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uzdkbtbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-services" {...props}></Icon>
