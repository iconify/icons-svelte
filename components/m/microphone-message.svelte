<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e24o_d0ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e24o_d0ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microphone-message" {...props}></Icon>
