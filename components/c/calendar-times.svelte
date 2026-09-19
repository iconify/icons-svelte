<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4bdfg_2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d4bdfg_2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calendar-times" {...props}></Icon>
