<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmj2aibcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmj2aibcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-penguin" {...props}></Icon>
