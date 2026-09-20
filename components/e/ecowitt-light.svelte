<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oos9bsboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oos9bsboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ecowitt-light" {...props}></Icon>
