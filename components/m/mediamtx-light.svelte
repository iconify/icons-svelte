<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds0s6f9to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds0s6f9to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamtx-light" {...props}></Icon>
