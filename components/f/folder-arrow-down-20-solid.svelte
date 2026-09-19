<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5q6tg5iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r5q6tg5iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-arrow-down-20-solid" {...props}></Icon>
