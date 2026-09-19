<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux23lm17f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ux23lm17f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apachekafka-wordmark" {...props}></Icon>
