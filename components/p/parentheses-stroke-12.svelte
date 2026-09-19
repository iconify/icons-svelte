<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgt6dvbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fgt6dvbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:parentheses-stroke-12" {...props}></Icon>
