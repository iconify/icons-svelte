<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0j8-xbhn.css';
import '../../css/z/z54z46b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0j8-xbhn"/><path class="z54z46b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clickhouse" {...props}></Icon>
