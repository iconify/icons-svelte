<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyinyrbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pyinyrbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:globe" {...props}></Icon>
