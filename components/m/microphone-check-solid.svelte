<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y_4x41bif.css';
import '../../css/d/d3p0atbag.css';
import '../../css/r/r-77_6bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y_4x41bif"/><rect class="d3p0atbag"/><path class="r-77_6bxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:microphone-check-solid" {...props}></Icon>
