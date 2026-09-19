<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylugypbul.css';
import '../../css/h/h35_vrvxl.css';
import '../../css/n/nevl0ie7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ylugypbul"/><path class="h35_vrvxl"/><path class="nevl0ie7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:phone-route-alt" {...props}></Icon>
