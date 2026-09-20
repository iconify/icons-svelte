<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqudbbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cvqudbbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-longhorn-light" {...props}></Icon>
