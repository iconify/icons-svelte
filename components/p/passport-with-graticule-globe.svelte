<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdf_24b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mdf_24b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:passport-with-graticule-globe" {...props}></Icon>
