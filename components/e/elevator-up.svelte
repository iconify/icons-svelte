<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxbldn1_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxbldn1_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevator-up" {...props}></Icon>
