<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfg3w-tef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gfg3w-tef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-justify-fill-12" {...props}></Icon>
