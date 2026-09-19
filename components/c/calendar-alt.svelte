<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlibchyrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="hlibchyrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:calendar-alt" {...props}></Icon>
