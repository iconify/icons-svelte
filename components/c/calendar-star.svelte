<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zycv9ym7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zycv9ym7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-star" {...props}></Icon>
