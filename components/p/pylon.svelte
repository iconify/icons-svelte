<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv0y7fdcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":98,"height":29};
const content = `<path class="pv0y7fdcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pylon" {...props}></Icon>
