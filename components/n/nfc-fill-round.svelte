<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6cj0vlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6cj0vlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:nfc-fill-round" {...props}></Icon>
