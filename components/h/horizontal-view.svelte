<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-icr-r2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s-icr-r2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:horizontal-view" {...props}></Icon>
