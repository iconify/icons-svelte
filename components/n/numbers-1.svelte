<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5yo_1bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5yo_1bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-1" {...props}></Icon>
