<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkt748d0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lkt748d0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:double-chevron-right" {...props}></Icon>
