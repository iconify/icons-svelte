<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5vde9b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="f5vde9b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grip-horizontal" {...props}></Icon>
