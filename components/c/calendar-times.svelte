<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzjwhcbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wzjwhcbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:calendar-times" {...props}></Icon>
