<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pew3ofbkh.css';
import '../../css/f/fp1_w-bip.css';
import '../../css/j/j57h7grwb.css';
import '../../css/o/opicw6a2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pew3ofbkh"/><path class="fp1_w-bip"/><path class="j57h7grwb"/><path class="opicw6a2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:elasticsearch-wordmark" {...props}></Icon>
