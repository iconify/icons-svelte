<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aktiaydcc.css';
import '../../css/c/c20n45bfn.css';
import '../../css/c/czv5jnbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aktiaydcc"/><path class="c20n45bfn"/><path class="czv5jnbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:draw-io" {...props}></Icon>
