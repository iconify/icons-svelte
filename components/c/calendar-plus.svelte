<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/manu--2ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="manu--2ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-plus" {...props}></Icon>
