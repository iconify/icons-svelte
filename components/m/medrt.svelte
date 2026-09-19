<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clyii8_rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":544,"height":512};
const content = `<path class="clyii8_rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:medrt" {...props}></Icon>
