<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj3-q5xdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="rj3-q5xdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:apple" {...props}></Icon>
