<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa_kbobxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="xa_kbobxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:hospital" {...props}></Icon>
