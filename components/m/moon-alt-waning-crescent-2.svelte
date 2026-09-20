<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2p6chu2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="z2p6chu2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-crescent-2" {...props}></Icon>
