<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgvl_034t.css';
import '../../css/y/yuy8pmq7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgvl_034t"/><path class="yuy8pmq7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-calendar-light" {...props}></Icon>
