<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygo-ekbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ygo-ekbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-chimney-and-door" {...props}></Icon>
