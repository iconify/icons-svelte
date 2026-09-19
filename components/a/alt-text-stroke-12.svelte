<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohrioug2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ohrioug2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alt-text-stroke-12" {...props}></Icon>
