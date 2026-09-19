<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t403b_11h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="t403b_11h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flagtriangle" {...props}></Icon>
