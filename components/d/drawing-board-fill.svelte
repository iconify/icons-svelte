<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3nskzbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3nskzbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawing-board-fill" {...props}></Icon>
