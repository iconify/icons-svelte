<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpna9sbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tpna9sbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:azimuth" {...props}></Icon>
