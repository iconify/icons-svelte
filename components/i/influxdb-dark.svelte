<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wup54xb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wup54xb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:influxdb-dark" {...props}></Icon>
