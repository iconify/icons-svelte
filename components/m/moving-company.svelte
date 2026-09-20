<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib88ljbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ib88ljbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:moving-company" {...props}></Icon>
