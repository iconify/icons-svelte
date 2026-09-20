<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fahwwo24s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fahwwo24s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pushpin-2-fill" {...props}></Icon>
