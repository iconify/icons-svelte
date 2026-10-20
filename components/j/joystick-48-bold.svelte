<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r20d5fbva.css';
import '../../css/o/o08gbrx6h.css';
import '../../css/c/cvogzw0ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r20d5fbva"/><path class="o08gbrx6h"/><path class="cvogzw0ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:joystick-48-bold" {...props}></Icon>
