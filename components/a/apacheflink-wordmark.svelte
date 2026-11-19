<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqcfp_zlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aqcfp_zlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:apacheflink-wordmark" {...props}></Icon>
