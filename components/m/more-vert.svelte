<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s91m03bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s91m03bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:more-vert" {...props}></Icon>
