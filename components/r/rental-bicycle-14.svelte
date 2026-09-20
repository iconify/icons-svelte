<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1ohwkm-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c1ohwkm-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:rental-bicycle-14" {...props}></Icon>
