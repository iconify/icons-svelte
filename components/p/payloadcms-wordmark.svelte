<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da46_l89g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="da46_l89g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:payloadcms-wordmark" {...props}></Icon>
