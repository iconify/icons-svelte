<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5q0xwacj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5q0xwacj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phoscon-light" {...props}></Icon>
