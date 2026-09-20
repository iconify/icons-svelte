<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfomdp99f.css';
import '../../css/i/i-5-10sby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<circle class="xfomdp99f"/><path class="i-5-10sby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:female" {...props}></Icon>
