<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7n9xvbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r7n9xvbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate-counterclockwise-filled" {...props}></Icon>
