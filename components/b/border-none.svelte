<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru6u8jb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ru6u8jb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:border-none" {...props}></Icon>
