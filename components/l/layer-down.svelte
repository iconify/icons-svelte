<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mppbu3ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mppbu3ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-down" {...props}></Icon>
