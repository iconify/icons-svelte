<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb1thxfbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="sb1thxfbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-diners-club" {...props}></Icon>
