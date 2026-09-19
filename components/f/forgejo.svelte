<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxx0avfpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nxx0avfpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:forgejo" {...props}></Icon>
