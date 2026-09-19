<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w782_ibba.css';
import '../../css/d/dk77dnbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w782_ibba"/><path class="dk77dnbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-planet" {...props}></Icon>
