<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxm4yjf1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxm4yjf1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:paint-fill" {...props}></Icon>
