<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an8dwl38i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an8dwl38i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glinr-dark" {...props}></Icon>
