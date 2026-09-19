<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcbt7yjkc.css';
import '../../css/s/sq6-edbzr.css';
import '../../css/b/bgw48cfvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xcbt7yjkc"/><path class="sq6-edbzr"/><path class="bgw48cfvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:labview" {...props}></Icon>
