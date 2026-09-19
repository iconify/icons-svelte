<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy1vs24lh.css';
import '../../css/k/k3-ivsvyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sy1vs24lh"/><path class="k3-ivsvyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gatsby-wordmark" {...props}></Icon>
