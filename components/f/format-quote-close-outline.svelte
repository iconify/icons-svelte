<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaq7q4l9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaq7q4l9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-quote-close-outline" {...props}></Icon>
