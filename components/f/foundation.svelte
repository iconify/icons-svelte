<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhcirroxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="yhcirroxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:foundation" {...props}></Icon>
