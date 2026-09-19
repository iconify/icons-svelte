<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn8l_w7lg.css';
import '../../css/o/ovur0mx_t.css';
import '../../css/t/tukbs_u6b.css';
import '../../css/t/twvlgd5yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yn8l_w7lg"/><circle class="ovur0mx_t"/><circle class="tukbs_u6b"/><path class="twvlgd5yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-compare-outline" {...props}></Icon>
