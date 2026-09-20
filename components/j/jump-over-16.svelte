<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv8a032vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zv8a032vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:jump-over-16" {...props}></Icon>
