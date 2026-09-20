<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlan15w3z.css';
import '../../css/g/ghlqhy24c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rlan15w3z"/><path class="ghlqhy24c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:graph" {...props}></Icon>
