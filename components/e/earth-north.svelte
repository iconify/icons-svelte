<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm_t8rd1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bm_t8rd1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-north" {...props}></Icon>
