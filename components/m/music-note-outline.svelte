<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi--f2b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi--f2b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-outline" {...props}></Icon>
