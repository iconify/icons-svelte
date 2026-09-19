<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et6f67bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="et6f67bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-alt-o" {...props}></Icon>
