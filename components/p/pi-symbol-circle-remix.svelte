<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjt6f0b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hjt6f0b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pi-symbol-circle-remix" {...props}></Icon>
