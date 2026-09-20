<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si3wqrb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="si3wqrb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:gym" {...props}></Icon>
