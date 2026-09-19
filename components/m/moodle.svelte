<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1jdvcbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1jdvcbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:moodle" {...props}></Icon>
