<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce4w8bc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ce4w8bc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:attachment" {...props}></Icon>
