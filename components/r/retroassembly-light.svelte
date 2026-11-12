<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9rc3cc_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9rc3cc_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:retroassembly-light" {...props}></Icon>
