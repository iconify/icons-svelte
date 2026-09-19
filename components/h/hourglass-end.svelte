<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i--uujb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i--uujb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hourglass-end" {...props}></Icon>
