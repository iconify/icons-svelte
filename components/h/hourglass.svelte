<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je9p0tb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="je9p0tb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:hourglass" {...props}></Icon>
