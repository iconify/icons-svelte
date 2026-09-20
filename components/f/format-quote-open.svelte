<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo_0ynbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo_0ynbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-quote-open" {...props}></Icon>
