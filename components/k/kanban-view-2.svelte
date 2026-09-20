<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhcab65mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhcab65mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:kanban-view-2" {...props}></Icon>
