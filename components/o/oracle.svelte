<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":231,"height":30};
const content = ``;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oracle" {...props}></Icon>
