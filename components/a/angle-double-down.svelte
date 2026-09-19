<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdkligb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="sdkligb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-double-down" {...props}></Icon>
