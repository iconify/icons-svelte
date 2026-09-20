<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej8ged-6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ej8ged-6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:globe" {...props}></Icon>
