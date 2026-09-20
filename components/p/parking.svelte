<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyzhkob9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="nyzhkob9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:parking" {...props}></Icon>
