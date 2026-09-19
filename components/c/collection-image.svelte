<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7381obji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="e7381obji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-image" {...props}></Icon>
