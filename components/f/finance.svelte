<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxk-ml5cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="gxk-ml5cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:finance" {...props}></Icon>
