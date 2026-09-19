<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozjoufbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ozjoufbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:netlify" {...props}></Icon>
