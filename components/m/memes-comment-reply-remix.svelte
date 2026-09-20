<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/por2i3b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="por2i3b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:memes-comment-reply-remix" {...props}></Icon>
