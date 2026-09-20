<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72gs7b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i72gs7b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:discussion-converstion-reply-remix" {...props}></Icon>
