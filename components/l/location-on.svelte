<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogq1sfe1k.css';
import '../../css/y/ylzgf4buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ogq1sfe1k"/><circle class="ylzgf4buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:location-on" {...props}></Icon>
