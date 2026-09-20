<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv60btb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zv60btb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-shrink-vertical-move-vertical-shrink" {...props}></Icon>
