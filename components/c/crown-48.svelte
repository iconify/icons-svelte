<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw607l8ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cw607l8ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crown-48" {...props}></Icon>
