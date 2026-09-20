<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6cu__b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p6cu__b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-2" {...props}></Icon>
