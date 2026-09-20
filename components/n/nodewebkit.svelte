<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ficz_mr3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ficz_mr3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nodewebkit" {...props}></Icon>
