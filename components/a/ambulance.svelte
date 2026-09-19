<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-0mx1beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1856,"height":1536};
const content = `<path class="e-0mx1beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ambulance" {...props}></Icon>
