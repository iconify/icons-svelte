<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5y0id6qu.css';
import '../../css/p/pyhgc0wha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a5y0id6qu"/><path class="pyhgc0wha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nimble" {...props}></Icon>
