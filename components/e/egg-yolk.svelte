<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caw1diebi.css';
import '../../css/s/sxij2rbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caw1diebi"/><path class="sxij2rbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:egg-yolk" {...props}></Icon>
