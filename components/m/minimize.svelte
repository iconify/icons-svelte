<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_p988bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_p988bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:minimize" {...props}></Icon>
