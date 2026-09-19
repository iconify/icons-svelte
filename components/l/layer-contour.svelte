<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl1yud0ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nl1yud0ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-contour" {...props}></Icon>
