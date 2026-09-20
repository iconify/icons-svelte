<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7-g_bb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7-g_bb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-minus-2" {...props}></Icon>
