<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3okiijpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j3okiijpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connect-target" {...props}></Icon>
