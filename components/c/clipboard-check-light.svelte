<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy-ztabgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hy-ztabgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:clipboard-check-light" {...props}></Icon>
