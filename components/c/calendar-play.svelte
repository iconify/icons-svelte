<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwp0bm6lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwp0bm6lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-play" {...props}></Icon>
