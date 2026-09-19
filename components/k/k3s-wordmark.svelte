<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thghjjkzc.css';
import '../../css/x/x97ig8bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="thghjjkzc"/><path class="x97ig8bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:k3s-wordmark" {...props}></Icon>
