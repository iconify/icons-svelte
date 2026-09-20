<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh_9m3lpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh_9m3lpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coathanger-line" {...props}></Icon>
