<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwus0ggfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vwus0ggfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:capacitor-wordmark" {...props}></Icon>
