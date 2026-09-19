<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syip1ku9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="syip1ku9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:north-arrow-n" {...props}></Icon>
