<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1_85zbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1_85zbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:influxdb-light" {...props}></Icon>
