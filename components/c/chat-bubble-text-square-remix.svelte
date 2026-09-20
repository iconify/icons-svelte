<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtycf5iik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rtycf5iik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:chat-bubble-text-square-remix" {...props}></Icon>
