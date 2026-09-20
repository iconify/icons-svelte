<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug8ynby4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ug8ynby4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-submariner-light" {...props}></Icon>
