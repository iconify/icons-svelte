<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0ooadc2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a0ooadc2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-fleet-dark" {...props}></Icon>
