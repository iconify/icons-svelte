<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntv6zhbei.css';
import '../../css/w/w5p1slozp.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ntv6zhbei"/><path class="w5p1slozp"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-plus-48" {...props}></Icon>
