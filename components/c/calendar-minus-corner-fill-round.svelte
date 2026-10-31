<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrgryxb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrgryxb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-minus-corner-fill-round" {...props}></Icon>
