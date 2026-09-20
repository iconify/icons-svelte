<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya901k8pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya901k8pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-fleet-light" {...props}></Icon>
