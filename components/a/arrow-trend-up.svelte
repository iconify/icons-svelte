<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj5x8lblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wj5x8lblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-trend-up" {...props}></Icon>
