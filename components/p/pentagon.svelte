<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft4g341fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ft4g341fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pentagon" {...props}></Icon>
