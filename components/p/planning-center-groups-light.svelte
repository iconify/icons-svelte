<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djbel3bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djbel3bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-groups-light" {...props}></Icon>
