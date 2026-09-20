<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp7mnabuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yp7mnabuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-translate-options-text-translate" {...props}></Icon>
