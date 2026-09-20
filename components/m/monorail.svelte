<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv43brb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vv43brb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:monorail" {...props}></Icon>
