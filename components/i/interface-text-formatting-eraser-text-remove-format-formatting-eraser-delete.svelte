<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq-uolocg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wq-uolocg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-eraser-text-remove-format-formatting-eraser-delete" {...props}></Icon>
