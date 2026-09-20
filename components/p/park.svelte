<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db6rklxru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="db6rklxru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:park" {...props}></Icon>
