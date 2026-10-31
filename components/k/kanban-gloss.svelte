<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhqw6obtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhqw6obtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:kanban-gloss" {...props}></Icon>
