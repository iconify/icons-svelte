<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfbprr8-v.css';
import '../../css/r/rd41_2bru.css';
import '../../css/t/tllvccb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vfbprr8-v"/><path class="rd41_2bru"/><g><path class="tllvccb_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-american-football" {...props}></Icon>
