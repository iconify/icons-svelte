<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgj33abyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgj33abyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-share" {...props}></Icon>
