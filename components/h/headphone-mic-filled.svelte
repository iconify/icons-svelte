<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drzam248w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drzam248w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:headphone-mic-filled" {...props}></Icon>
