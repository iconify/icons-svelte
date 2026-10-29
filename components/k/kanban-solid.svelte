<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acayooksy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acayooksy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:kanban-solid" {...props}></Icon>
