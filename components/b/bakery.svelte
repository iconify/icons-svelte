<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq_gk5baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="pq_gk5baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:bakery" {...props}></Icon>
