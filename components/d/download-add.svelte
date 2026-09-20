<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auvh3l48q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="auvh3l48q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:download-add" {...props}></Icon>
