<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz9x4_4-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="oz9x4_4-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:amusement-park" {...props}></Icon>
