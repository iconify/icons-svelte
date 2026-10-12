<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvl7hibfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wvl7hibfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-square-20-bold" {...props}></Icon>
