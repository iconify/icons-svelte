<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh-vg0nom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qh-vg0nom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:creative-commons-dark" {...props}></Icon>
