<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p69oc7ijo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="p69oc7ijo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:calendar-check" {...props}></Icon>
