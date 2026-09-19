<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvq7rx58k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="dvq7rx58k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:people-arrows" {...props}></Icon>
