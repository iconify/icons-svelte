<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9l2cibtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9l2cibtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-week-end-outline" {...props}></Icon>
