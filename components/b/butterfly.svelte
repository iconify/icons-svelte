<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi8-49b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="yi8-49b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:butterfly" {...props}></Icon>
