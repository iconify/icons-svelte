<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxr1szbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxr1szbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pi-hole" {...props}></Icon>
