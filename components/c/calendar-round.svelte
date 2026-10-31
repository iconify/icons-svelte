<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jol785xfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jol785xfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-round" {...props}></Icon>
