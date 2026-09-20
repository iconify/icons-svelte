<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oex3cvbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oex3cvbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:optimize" {...props}></Icon>
