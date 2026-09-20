<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehev4sv_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ehev4sv_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:real-estate-agency" {...props}></Icon>
