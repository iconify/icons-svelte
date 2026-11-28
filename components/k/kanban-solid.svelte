<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onfod63xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onfod63xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:kanban-solid" {...props}></Icon>
