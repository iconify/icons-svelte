<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewezq1b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ewezq1b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-road" {...props}></Icon>
