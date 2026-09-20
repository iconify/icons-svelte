<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4a4zcb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r4a4zcb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ie10" {...props}></Icon>
