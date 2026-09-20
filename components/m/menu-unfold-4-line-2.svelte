<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylyopj0xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylyopj0xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-4-line-2" {...props}></Icon>
