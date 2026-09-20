<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sci_v2bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="sci_v2bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:airport" {...props}></Icon>
