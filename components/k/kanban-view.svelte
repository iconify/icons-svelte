<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyo9g4bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyo9g4bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:kanban-view" {...props}></Icon>
