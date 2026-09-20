<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i00exacev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="i00exacev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:department-store" {...props}></Icon>
