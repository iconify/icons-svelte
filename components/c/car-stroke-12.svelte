<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdla-ibad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rdla-ibad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:car-stroke-12" {...props}></Icon>
