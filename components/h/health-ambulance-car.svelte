<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbva30-wv.css';
import '../../css/h/hs2nkdwup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xbva30-wv"/><path class="hs2nkdwup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-ambulance-car" {...props}></Icon>
