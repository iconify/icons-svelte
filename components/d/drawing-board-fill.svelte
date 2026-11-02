<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jppu-ub8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jppu-ub8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawing-board-fill" {...props}></Icon>
