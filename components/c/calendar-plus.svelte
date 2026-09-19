<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7wj43brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r7wj43brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:calendar-plus" {...props}></Icon>
