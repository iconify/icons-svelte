<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-tjpjsqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="e-tjpjsqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:health" {...props}></Icon>
