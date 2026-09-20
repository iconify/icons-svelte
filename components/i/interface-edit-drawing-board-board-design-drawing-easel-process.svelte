<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3gl5vbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e3gl5vbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-drawing-board-board-design-drawing-easel-process" {...props}></Icon>
