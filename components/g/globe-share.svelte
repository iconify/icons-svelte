<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6u974y3x.css';
import '../../css/a/a19ub-b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g6u974y3x"/><path class="a19ub-b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-share" {...props}></Icon>
