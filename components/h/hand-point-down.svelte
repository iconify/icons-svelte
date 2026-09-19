<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avbi9obof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="avbi9obof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-point-down" {...props}></Icon>
