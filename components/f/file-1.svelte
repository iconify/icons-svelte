<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wctfu3bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wctfu3bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-1" {...props}></Icon>
