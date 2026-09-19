<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0pjxttfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="y0pjxttfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bell-slash-o" {...props}></Icon>
