<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj5qwhlnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1536};
const content = `<path class="sj5qwhlnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:moon-o" {...props}></Icon>
