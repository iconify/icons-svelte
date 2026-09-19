<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am1mhwe5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am1mhwe5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-calendar-star" {...props}></Icon>
