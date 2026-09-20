<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_l_wdbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="l_l_wdbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:closed-captioning" {...props}></Icon>
