<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of__6dbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of__6dbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-play" {...props}></Icon>
