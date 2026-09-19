<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2z2trbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q2z2trbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flow-map" {...props}></Icon>
