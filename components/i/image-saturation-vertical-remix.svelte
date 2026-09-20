<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohzy11owu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ohzy11owu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-saturation-vertical-remix" {...props}></Icon>
