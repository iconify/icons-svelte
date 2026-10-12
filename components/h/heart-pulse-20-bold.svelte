<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_oeqshiy.css';
import '../../css/v/v7-hzldcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a_oeqshiy"/><path class="v7-hzldcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-pulse-20-bold" {...props}></Icon>
