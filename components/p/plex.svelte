<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_oop1bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_oop1bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:plex" {...props}></Icon>
