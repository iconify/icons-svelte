<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8q8fgbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i8q8fgbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:brave" {...props}></Icon>
