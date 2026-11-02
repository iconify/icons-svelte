<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw2aebcvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw2aebcvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-cloudy-fill" {...props}></Icon>
