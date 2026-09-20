<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks1yeixst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ks1yeixst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-5" {...props}></Icon>
