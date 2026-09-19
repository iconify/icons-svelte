<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeae1zb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xeae1zb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:redux" {...props}></Icon>
