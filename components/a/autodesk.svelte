<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssd_2ibyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssd_2ibyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:autodesk" {...props}></Icon>
