<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6p4noldf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m6p4noldf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:calendar" {...props}></Icon>
