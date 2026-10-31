<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvzc5l46x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvzc5l46x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-week-fill-round" {...props}></Icon>
