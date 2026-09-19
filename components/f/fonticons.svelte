<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi6co0b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wi6co0b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:fonticons" {...props}></Icon>
