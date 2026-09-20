<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd80xzbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd80xzbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:autodesk-revit" {...props}></Icon>
