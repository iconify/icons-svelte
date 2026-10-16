<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcia1ds6l.css';
import '../../css/y/yl40te36f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="yl40te36f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-explosive-20-bold" {...props}></Icon>
