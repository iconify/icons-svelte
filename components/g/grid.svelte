<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn1iq6wxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gn1iq6wxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:grid" {...props}></Icon>
