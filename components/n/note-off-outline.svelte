<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwpejvwmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwpejvwmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:note-off-outline" {...props}></Icon>
