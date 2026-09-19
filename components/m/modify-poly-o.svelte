<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfn3ybbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rfn3ybbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:modify-poly-o" {...props}></Icon>
