<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gma850bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="gma850bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:calendar-plus-o" {...props}></Icon>
