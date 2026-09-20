<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmgzy2b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tmgzy2b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-cloudy" {...props}></Icon>
