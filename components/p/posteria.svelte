<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys8turbgx.css';
import '../../css/r/r5bfu2tfk.css';
import '../../css/e/e8ygrwbil.css';
import '../../css/q/q75jjebbk.css';
import '../../css/z/zz-ow3bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys8turbgx"/><path class="r5bfu2tfk"/><path class="e8ygrwbil"/><circle class="q75jjebbk"/><path class="zz-ow3bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:posteria" {...props}></Icon>
