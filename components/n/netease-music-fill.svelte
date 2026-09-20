<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri8ga0brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri8ga0brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:netease-music-fill" {...props}></Icon>
