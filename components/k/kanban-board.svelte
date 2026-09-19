<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh7ourc9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh7ourc9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:kanban-board" {...props}></Icon>
