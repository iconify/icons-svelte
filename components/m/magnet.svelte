<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwb4r1b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jwb4r1b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:magnet" {...props}></Icon>
