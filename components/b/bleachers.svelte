<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su32ojj2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="su32ojj2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bleachers" {...props}></Icon>
