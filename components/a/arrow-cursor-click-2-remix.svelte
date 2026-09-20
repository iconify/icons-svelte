<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcgn7ho-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rcgn7ho-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-cursor-click-2-remix" {...props}></Icon>
