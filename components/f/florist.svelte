<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aspcfwdmv.css';
import '../../css/a/ar92us5lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<ellipse class="aspcfwdmv"/><path class="ar92us5lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:florist" {...props}></Icon>
