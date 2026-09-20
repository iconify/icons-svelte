<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu7h6bc4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xu7h6bc4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ice-cream-2-remix" {...props}></Icon>
