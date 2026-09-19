<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3imq2azo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j3imq2azo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paint-brush-20-solid" {...props}></Icon>
