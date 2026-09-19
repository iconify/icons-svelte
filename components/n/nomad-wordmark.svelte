<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzj42ixdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hzj42ixdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nomad-wordmark" {...props}></Icon>
