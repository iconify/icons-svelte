<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sspvm51wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sspvm51wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:os-patch-management" {...props}></Icon>
