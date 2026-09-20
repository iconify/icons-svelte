<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjnly3blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xjnly3blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openapi" {...props}></Icon>
