<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbfsq-g3p.css';
import '../../css/w/w5v4f9b3d.css';
import '../../css/j/jpv6g7hti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":130};
const content = `<path class="mbfsq-g3p"/><path class="w5v4f9b3d"/><path class="jpv6g7hti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-workspace-wordmark-light" {...props}></Icon>
