<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yol05lbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="yol05lbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:cloud-refresh" {...props}></Icon>
