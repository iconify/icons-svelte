<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3omditqb.css';
import '../../css/a/aznntcc2l.css';
import '../../css/r/rlpyj51xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3omditqb"/><path class="aznntcc2l"/><path class="rlpyj51xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:casaos" {...props}></Icon>
