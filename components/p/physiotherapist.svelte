<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi0hxlbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zi0hxlbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:physiotherapist" {...props}></Icon>
