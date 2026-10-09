<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjvohhboi.css';
import '../../css/w/wrlhybbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tjvohhboi"/><path class="wrlhybbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bonfire-20" {...props}></Icon>
