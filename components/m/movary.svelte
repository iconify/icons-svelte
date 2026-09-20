<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzuuxyv1b.css';
import '../../css/e/e9w0n4t1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzuuxyv1b"/><path class="e9w0n4t1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:movary" {...props}></Icon>
