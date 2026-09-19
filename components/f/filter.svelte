<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxt_ksb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxt_ksb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:filter" {...props}></Icon>
