<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4__6ibfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4__6ibfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rewind-45" {...props}></Icon>
