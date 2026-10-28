<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn2z21zcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jn2z21zcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:neon" {...props}></Icon>
