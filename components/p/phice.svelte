<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw3y1unhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw3y1unhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phice" {...props}></Icon>
