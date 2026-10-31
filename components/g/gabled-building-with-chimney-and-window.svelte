<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb4moactm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zb4moactm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-chimney-and-window" {...props}></Icon>
