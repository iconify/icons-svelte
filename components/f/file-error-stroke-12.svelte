<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yasyzz4_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yasyzz4_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-error-stroke-12" {...props}></Icon>
