<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exa0pjb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="exa0pjb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-route" {...props}></Icon>
