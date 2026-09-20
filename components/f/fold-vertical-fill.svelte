<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3v3u4bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3v3u4bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-vertical-fill" {...props}></Icon>
