<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlnn0ibiz.css';
import '../../css/e/e_rm4btzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nlnn0ibiz"/><path class="e_rm4btzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:map-location" {...props}></Icon>
