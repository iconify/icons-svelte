<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhbsobbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhbsobbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:costco-light" {...props}></Icon>
