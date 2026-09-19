<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwdip1fdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cwdip1fdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:reflex" {...props}></Icon>
