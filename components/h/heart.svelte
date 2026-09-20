<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5zmk_xeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z5zmk_xeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:heart" {...props}></Icon>
