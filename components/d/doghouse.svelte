<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w53ucybhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="w53ucybhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:doghouse" {...props}></Icon>
