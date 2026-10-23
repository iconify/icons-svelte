<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fozb4jemz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fozb4jemz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-arrow-down" {...props}></Icon>
