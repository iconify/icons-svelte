<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km0j_jb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km0j_jb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-down" {...props}></Icon>
