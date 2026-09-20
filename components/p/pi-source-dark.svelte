<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc4jvnbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pc4jvnbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-source-dark" {...props}></Icon>
