<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luts3yb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="luts3yb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:natural-feature" {...props}></Icon>
