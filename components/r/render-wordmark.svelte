<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_scynb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k_scynb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:render-wordmark" {...props}></Icon>
