<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e13j-rb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e13j-rb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:directx-wordmark" {...props}></Icon>
