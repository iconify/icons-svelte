<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9f_hdcju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9f_hdcju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:job-run" {...props}></Icon>
