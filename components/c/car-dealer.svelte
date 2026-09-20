<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh8h2dyiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fh8h2dyiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:car-dealer" {...props}></Icon>
