<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuaxh5aru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zuaxh5aru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:framework7" {...props}></Icon>
