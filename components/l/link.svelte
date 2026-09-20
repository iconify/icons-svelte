<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvs_m-bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kvs_m-bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:link" {...props}></Icon>
