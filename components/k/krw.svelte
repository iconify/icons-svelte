<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrdg4tgbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rrdg4tgbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:krw" {...props}></Icon>
