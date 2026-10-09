<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aum7pfzqi.css';
import '../../css/l/leb4hvjgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aum7pfzqi"/><path class="leb4hvjgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-days-20-bold" {...props}></Icon>
