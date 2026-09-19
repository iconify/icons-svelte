<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsttf0l7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wsttf0l7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chess-knight" {...props}></Icon>
