<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2d-zbcwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q2d-zbcwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:directions" {...props}></Icon>
