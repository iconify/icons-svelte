<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myr8txt8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myr8txt8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-eighth-dotted" {...props}></Icon>
