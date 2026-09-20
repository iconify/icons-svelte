<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr-i3_k_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cr-i3_k_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:okd-light" {...props}></Icon>
