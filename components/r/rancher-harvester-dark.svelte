<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqo7_ubqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fqo7_ubqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-harvester-dark" {...props}></Icon>
