<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0mw04lqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i0mw04lqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:appearance" {...props}></Icon>
