<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzp7s2bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzp7s2bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawing-board-line" {...props}></Icon>
