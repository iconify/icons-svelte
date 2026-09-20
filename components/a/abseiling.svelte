<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhrvhjdxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="xhrvhjdxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:abseiling" {...props}></Icon>
