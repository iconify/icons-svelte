<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_r9kvaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6_r9kvaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amd-light" {...props}></Icon>
