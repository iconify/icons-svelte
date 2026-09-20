<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc58hgots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oc58hgots"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:aarch64" {...props}></Icon>
