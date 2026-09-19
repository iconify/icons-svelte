<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz_6x620o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1536};
const content = `<path class="tz_6x620o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:get-pocket" {...props}></Icon>
