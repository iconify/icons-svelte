<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfvu3vb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vfvu3vb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:polaroid-four-remix" {...props}></Icon>
