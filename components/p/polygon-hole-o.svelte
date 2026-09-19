<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8yu3ealr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="l8yu3ealr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polygon-hole-o" {...props}></Icon>
