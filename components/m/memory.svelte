<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj7kwhbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zj7kwhbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:memory" {...props}></Icon>
