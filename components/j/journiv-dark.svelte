<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgs5ujm3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgs5ujm3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:journiv-dark" {...props}></Icon>
