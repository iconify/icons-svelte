<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2gmwachp.css';
import '../../css/x/xwt0ly2qh.css';
import '../../css/y/ys7g5m00i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2gmwachp"/><path class="xwt0ly2qh"/><path class="ys7g5m00i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qdrant-light" {...props}></Icon>
