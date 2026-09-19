<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cif8afbhr.css';
import '../../css/y/y9fgjabwe.css';
import '../../css/z/zer1teyxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cif8afbhr"/><path class="y9fgjabwe"/><path class="zer1teyxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:plotly-wordmark" {...props}></Icon>
