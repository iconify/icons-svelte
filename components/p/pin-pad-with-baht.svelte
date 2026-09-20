<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ponj89bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ponj89bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-baht" {...props}></Icon>
