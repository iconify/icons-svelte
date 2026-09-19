<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlugsnb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wlugsnb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-stack" {...props}></Icon>
