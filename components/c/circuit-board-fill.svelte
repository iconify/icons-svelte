<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dggbul2sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dggbul2sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circuit-board-fill" {...props}></Icon>
