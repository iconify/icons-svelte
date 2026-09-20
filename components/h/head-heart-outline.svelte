<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zihqgnbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zihqgnbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-heart-outline" {...props}></Icon>
