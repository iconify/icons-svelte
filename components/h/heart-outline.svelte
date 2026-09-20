<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ab7fbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t8ab7fbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:heart-outline" {...props}></Icon>
