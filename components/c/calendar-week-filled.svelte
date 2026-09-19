<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6p0cw7og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6p0cw7og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-week-filled" {...props}></Icon>
