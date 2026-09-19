<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6l8pobbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="v6l8pobbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:calendar-plus" {...props}></Icon>
