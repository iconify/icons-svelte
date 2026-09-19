<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo41iqbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jo41iqbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:car-tunnel" {...props}></Icon>
