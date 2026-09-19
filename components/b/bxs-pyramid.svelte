<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh3esxb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh3esxb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-pyramid" {...props}></Icon>
