<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro9ew8b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro9ew8b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:microphone-off-filled" {...props}></Icon>
