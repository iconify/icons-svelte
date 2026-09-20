<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n02g9eb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n02g9eb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-text-square-remix" {...props}></Icon>
