<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zr2nxeb2j.css';
import '../../css/u/urdmwybfb.css';
import '../../css/w/w79zl5b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zr2nxeb2j"/><path class="urdmwybfb"/><path class="w79zl5b-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-sparkles-sharp-two-tone" {...props}></Icon>
