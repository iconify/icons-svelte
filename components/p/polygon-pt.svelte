<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vey7tzb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vey7tzb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polygon-pt" {...props}></Icon>
