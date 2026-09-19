<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0asqjhxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0asqjhxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:list-ul" {...props}></Icon>
