<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdt2tgb-r.css';
import '../../css/p/p__bsbi5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdt2tgb-r"/><path class="p__bsbi5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calagopus-dark" {...props}></Icon>
