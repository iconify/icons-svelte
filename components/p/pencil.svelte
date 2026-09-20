<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh6cq6a0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh6cq6a0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil" {...props}></Icon>
