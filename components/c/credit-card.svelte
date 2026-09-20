<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa5fotm2d.css';
import '../../css/w/w__f9-ryl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pa5fotm2d"/><path class="w__f9-ryl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:credit-card" {...props}></Icon>
