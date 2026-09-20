<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvh4yw4zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvh4yw4zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fnos-dark" {...props}></Icon>
