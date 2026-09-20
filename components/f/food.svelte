<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zceg7w4_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zceg7w4_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:food" {...props}></Icon>
