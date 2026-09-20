<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npvyk8bwj.css';
import '../../css/o/otc7hdckt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npvyk8bwj"/><path class="otc7hdckt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bluetooth" {...props}></Icon>
