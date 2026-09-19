<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqltz0bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bqltz0bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:photonengine" {...props}></Icon>
