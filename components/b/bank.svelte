<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s17iqx8kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="s17iqx8kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:bank" {...props}></Icon>
