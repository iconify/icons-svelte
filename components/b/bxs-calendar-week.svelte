<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upwo9zbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upwo9zbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-calendar-week" {...props}></Icon>
