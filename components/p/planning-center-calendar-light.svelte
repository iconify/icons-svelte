<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvq731b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvq731b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-calendar-light" {...props}></Icon>
