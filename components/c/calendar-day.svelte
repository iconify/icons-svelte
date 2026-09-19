<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy9emkllg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sy9emkllg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calendar-day" {...props}></Icon>
