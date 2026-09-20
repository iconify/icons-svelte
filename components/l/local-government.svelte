<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnke7lehf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="gnke7lehf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:local-government" {...props}></Icon>
