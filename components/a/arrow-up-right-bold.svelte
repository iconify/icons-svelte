<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3pjjhbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3pjjhbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-right-bold" {...props}></Icon>
