<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwrycbbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vwrycbbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:i3s-web" {...props}></Icon>
