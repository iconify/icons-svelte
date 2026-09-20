<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je8zd7f2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je8zd7f2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-download-line" {...props}></Icon>
