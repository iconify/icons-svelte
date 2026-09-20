<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uicp4xbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uicp4xbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qzone" {...props}></Icon>
