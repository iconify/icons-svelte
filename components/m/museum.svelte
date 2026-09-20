<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn13oacbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="cn13oacbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:museum" {...props}></Icon>
