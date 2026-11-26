<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmljcx80c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fmljcx80c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glinr-light" {...props}></Icon>
