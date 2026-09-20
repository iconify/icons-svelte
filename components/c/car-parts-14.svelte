<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uawyetb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uawyetb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:car-parts-14" {...props}></Icon>
