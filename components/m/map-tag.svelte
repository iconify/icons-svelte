<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggiu84btg.css';
import '../../css/l/lwi--_w_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ggiu84btg"/><path class="lwi--_w_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-tag" {...props}></Icon>
