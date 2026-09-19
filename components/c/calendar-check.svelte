<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_xvtz4fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i_xvtz4fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:calendar-check" {...props}></Icon>
