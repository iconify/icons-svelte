<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8txeybqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a8txeybqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:bookmark-outline-add" {...props}></Icon>
