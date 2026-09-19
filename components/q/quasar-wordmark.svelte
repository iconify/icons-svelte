<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mddf--b2d.css';
import '../../css/k/k3s0atbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mddf--b2d"/><path class="k3s0atbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:quasar-wordmark" {...props}></Icon>
