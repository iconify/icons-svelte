<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffl2fn4uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ffl2fn4uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-euro-africa" {...props}></Icon>
