<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_vin0b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_vin0b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:digital-clock" {...props}></Icon>
