<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqb03cb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hqb03cb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:bowling-alley" {...props}></Icon>
