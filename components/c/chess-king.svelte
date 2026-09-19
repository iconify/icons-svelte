<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsje7487x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fsje7487x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chess-king" {...props}></Icon>
