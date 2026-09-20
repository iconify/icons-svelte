<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au5ft3ime.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="au5ft3ime"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-rio" {...props}></Icon>
