<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr___x8pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":456};
const content = `<path class="gr___x8pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bing" {...props}></Icon>
