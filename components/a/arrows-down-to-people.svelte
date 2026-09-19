<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxdwi4bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jxdwi4bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-down-to-people" {...props}></Icon>
