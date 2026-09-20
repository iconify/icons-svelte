<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q42marync.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="q42marync"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:city-hall" {...props}></Icon>
