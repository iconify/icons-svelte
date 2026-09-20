<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmmy86dde.css';
import '../../css/s/sva9mubnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmmy86dde"/><path class="sva9mubnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feeds-fun" {...props}></Icon>
