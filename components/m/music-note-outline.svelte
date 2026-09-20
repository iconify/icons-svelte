<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt7tz5iod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dt7tz5iod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-outline" {...props}></Icon>
