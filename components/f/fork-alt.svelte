<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_9-ozbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t_9-ozbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:fork-alt" {...props}></Icon>
