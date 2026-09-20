<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drw4f59_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drw4f59_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-line" {...props}></Icon>
