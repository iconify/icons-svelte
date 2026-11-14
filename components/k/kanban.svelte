<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct-bc_bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct-bc_bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:kanban" {...props}></Icon>
