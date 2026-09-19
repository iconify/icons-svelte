<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-c76yb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x-c76yb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:poll" {...props}></Icon>
