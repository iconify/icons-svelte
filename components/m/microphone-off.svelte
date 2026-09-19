<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjzh2jrou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjzh2jrou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:microphone-off" {...props}></Icon>
