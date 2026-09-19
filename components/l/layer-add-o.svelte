<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2m-lcscl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k2m-lcscl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-add-o" {...props}></Icon>
