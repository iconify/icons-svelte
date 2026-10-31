<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frp7d067u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frp7d067u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-double-left-round" {...props}></Icon>
