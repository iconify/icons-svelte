<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrgp7_b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hrgp7_b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:camper-trailer" {...props}></Icon>
