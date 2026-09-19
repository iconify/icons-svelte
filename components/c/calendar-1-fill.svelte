<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9uy8gbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9uy8gbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-1-fill" {...props}></Icon>
