<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9g01ubhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9g01ubhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-on-line" {...props}></Icon>
