<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaa_36bkr.css';
import '../../css/a/azcm8kehl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zaa_36bkr"/><path class="azcm8kehl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:duckduckgo-dark" {...props}></Icon>
