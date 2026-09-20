<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfzzc2b4k.css';
import '../../css/e/e558ozb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfzzc2b4k"/><path class="e558ozb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa-light" {...props}></Icon>
