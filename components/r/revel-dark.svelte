<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5wb8rbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5wb8rbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revel-dark" {...props}></Icon>
