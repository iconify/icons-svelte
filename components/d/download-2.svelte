<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np2o43-0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np2o43-0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:download-2" {...props}></Icon>
