<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt6acgbrk.css';
import '../../css/t/tk0tl-b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yt6acgbrk"/><path class="tk0tl-b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:newspaper-16-solid" {...props}></Icon>
