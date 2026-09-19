<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-roltbpz.css';
import '../../css/t/thf8vdb1b.css';
import '../../css/o/oxcajzmoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-roltbpz"/><path class="thf8vdb1b"/><path class="oxcajzmoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:aubergine" {...props}></Icon>
