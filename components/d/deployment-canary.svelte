<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-s-y5s8p.css';
import '../../css/w/w_-ne2bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="u-s-y5s8p"/><path class="w_-ne2bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-canary" {...props}></Icon>
