<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh88yn8ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh88yn8ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-up-left-fill" {...props}></Icon>
