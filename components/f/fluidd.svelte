<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf_1mybtb.css';
import '../../css/r/r2pseab2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sf_1mybtb"/><path class="r2pseab2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluidd" {...props}></Icon>
