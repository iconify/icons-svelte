<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck_pfnhtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ck_pfnhtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency-baht" {...props}></Icon>
