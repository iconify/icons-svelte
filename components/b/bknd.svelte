<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgdewob5q.css';
import '../../css/u/uuvbm1wfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgdewob5q"/><path class="uuvbm1wfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bknd" {...props}></Icon>
