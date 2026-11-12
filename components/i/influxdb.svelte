<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dajvep74v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dajvep74v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:influxdb" {...props}></Icon>
