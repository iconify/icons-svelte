<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaqegsb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jaqegsb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:car-rental" {...props}></Icon>
