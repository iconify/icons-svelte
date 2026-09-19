<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1cg_brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1cg_brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-file-01" {...props}></Icon>
