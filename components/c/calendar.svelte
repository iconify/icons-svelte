<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifjip30_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ifjip30_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:calendar" {...props}></Icon>
