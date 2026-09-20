<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gufcdpbgn.css';
import '../../css/o/oxn1-zbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gufcdpbgn"/><path class="oxn1-zbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apl" {...props}></Icon>
