<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja3adethd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja3adethd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hd-line" {...props}></Icon>
