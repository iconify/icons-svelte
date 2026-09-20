<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wica53iwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wica53iwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-longhorn-dark" {...props}></Icon>
