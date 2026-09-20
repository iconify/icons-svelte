<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmu6_gbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="lmu6_gbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:hang-gliding" {...props}></Icon>
