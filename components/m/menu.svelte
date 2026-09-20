<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d48z85b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d48z85b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:menu" {...props}></Icon>
