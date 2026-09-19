<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jldw8tb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jldw8tb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:money-bill" {...props}></Icon>
