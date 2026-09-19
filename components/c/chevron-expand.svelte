<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9bdhbbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9bdhbbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-expand" {...props}></Icon>
