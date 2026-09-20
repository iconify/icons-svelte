<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8jmq4o5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="s8jmq4o5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:graph-box" {...props}></Icon>
