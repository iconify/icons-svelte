<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpd0b1bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpd0b1bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-kanban-solid" {...props}></Icon>
