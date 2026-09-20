<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdq7pzc7k.css';
import '../../css/o/ov7ogjxth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdq7pzc7k"/><path class="ov7ogjxth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:conversation-chat" {...props}></Icon>
