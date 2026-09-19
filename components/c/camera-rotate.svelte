<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtue6_b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qtue6_b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:camera-rotate" {...props}></Icon>
