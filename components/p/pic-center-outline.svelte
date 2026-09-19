<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-zt0ibhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w-zt0ibhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pic-center-outline" {...props}></Icon>
