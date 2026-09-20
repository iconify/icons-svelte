<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey6w3zw8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ey6w3zw8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:dots-horizontal-triple" {...props}></Icon>
