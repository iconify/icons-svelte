<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwpyakbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hwpyakbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:music-remove" {...props}></Icon>
