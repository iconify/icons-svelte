<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhwraxbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhwraxbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-flute" {...props}></Icon>
