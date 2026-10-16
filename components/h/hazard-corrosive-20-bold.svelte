<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcia1ds6l.css';
import '../../css/z/z75rrmhbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="z75rrmhbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-corrosive-20-bold" {...props}></Icon>
