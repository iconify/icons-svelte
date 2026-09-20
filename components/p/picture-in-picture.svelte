<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dguxuj9xv.css';
import '../../css/h/hu6j50bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dguxuj9xv"/><path class="hu6j50bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:picture-in-picture" {...props}></Icon>
