<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_5vw5y9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_5vw5y9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ciencia-vitae" {...props}></Icon>
