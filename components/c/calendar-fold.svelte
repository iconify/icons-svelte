<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag76r2btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag76r2btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-fold" {...props}></Icon>
