<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3bsu7bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n3bsu7bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jule" {...props}></Icon>
