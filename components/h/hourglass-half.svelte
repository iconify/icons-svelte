<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjihvab5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jjihvab5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hourglass-half" {...props}></Icon>
