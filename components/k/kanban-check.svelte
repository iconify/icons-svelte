<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ascu7acom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ascu7acom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:kanban-check" {...props}></Icon>
