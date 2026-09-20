<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn5ah_bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nn5ah_bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:golang-dark" {...props}></Icon>
