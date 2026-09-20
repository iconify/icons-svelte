<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze5oi5l2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ze5oi5l2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-down" {...props}></Icon>
