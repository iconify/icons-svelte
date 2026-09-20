<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp5_vtb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp5_vtb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-heart-multiple" {...props}></Icon>
