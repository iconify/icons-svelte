<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6h1pk2wx.css';
import '../../css/k/kj5yxug5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6h1pk2wx"/><path class="kj5yxug5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-camera-off" {...props}></Icon>
