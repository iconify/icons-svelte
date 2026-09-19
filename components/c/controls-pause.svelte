<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0i-ett0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d0i-ett0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:controls-pause" {...props}></Icon>
