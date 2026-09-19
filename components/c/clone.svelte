<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iokcg5b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iokcg5b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:clone" {...props}></Icon>
