<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw1ob8z1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw1ob8z1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kanban-square-bold" {...props}></Icon>
