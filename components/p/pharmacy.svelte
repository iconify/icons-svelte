<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0g4jgwls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="r0g4jgwls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:pharmacy" {...props}></Icon>
