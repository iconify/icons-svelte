<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuew33vie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yuew33vie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:heart" {...props}></Icon>
