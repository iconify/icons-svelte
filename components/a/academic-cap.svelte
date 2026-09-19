<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgbhl21qs.css';
import '../../css/y/yo019rtxz.css';
import '../../css/i/il854jbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mgbhl21qs"/><path class="yo019rtxz"/><path class="il854jbvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:academic-cap" {...props}></Icon>
