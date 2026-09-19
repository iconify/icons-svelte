<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqalf3b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqalf3b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:firefox" {...props}></Icon>
