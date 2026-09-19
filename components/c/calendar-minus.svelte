<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pej60j-lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pej60j-lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:calendar-minus" {...props}></Icon>
