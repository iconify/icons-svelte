<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqtld7bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nqtld7bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:help-rarrow" {...props}></Icon>
