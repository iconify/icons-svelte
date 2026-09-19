<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf8b3dbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bf8b3dbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:babel" {...props}></Icon>
