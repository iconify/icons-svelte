<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o32qdsbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o32qdsbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dashcube" {...props}></Icon>
