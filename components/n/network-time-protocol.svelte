<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zilrarrlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zilrarrlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-time-protocol" {...props}></Icon>
