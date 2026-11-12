<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgnha726h.css';
import '../../css/z/zhef83wqk.css';
import '../../css/z/zuvme35ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tgnha726h"/><path class="zhef83wqk"/><path class="zuvme35ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kpaste-dark" {...props}></Icon>
