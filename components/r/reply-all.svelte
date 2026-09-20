<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p30cfwbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p30cfwbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:reply-all" {...props}></Icon>
