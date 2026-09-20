<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duxijwb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duxijwb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pan-top-right" {...props}></Icon>
