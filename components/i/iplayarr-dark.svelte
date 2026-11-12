<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z43uply2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z43uply2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iplayarr-dark" {...props}></Icon>
