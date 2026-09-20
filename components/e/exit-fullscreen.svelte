<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8kuy1ofz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q8kuy1ofz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:exit-fullscreen" {...props}></Icon>
