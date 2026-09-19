<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1t9b8bvt.css';
import '../../css/m/mr-kkz0yl.css';
import '../../css/i/imxhuacrw.css';
import '../../css/n/n839ahj1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1t9b8bvt"/><path class="mr-kkz0yl"/><path class="imxhuacrw"/><g><path class="n839ahj1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-list" {...props}></Icon>
