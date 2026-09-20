<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pimlciajz.css';
import '../../css/d/da73u8bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="pimlciajz"/><path class="da73u8bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:info" {...props}></Icon>
