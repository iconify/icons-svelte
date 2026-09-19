<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wur_xks1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wur_xks1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-america" {...props}></Icon>
