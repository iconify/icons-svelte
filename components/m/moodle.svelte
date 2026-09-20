<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztfe2y7ay.css';
import '../../css/u/u_faizb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztfe2y7ay"/><path class="u_faizb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moodle" {...props}></Icon>
