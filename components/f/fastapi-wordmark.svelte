<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkljh-dxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qkljh-dxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fastapi-wordmark" {...props}></Icon>
