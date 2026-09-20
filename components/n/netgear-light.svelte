<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfv5vpb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfv5vpb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netgear-light" {...props}></Icon>
