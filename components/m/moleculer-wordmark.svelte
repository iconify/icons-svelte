<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0x0msb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a0x0msb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:moleculer-wordmark" {...props}></Icon>
