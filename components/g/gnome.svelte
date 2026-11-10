<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5-l4ub-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m5-l4ub-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gnome" {...props}></Icon>
