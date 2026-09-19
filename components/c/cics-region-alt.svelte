<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu7m3979e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wu7m3979e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-region-alt" {...props}></Icon>
