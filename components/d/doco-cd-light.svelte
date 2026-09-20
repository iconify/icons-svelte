<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unrev1bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unrev1bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:doco-cd-light" {...props}></Icon>
