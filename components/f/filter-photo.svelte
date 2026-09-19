<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4sk93ouz.css';
import '../../css/z/zqq79db7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4sk93ouz"/><path class="zqq79db7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:filter-photo" {...props}></Icon>
