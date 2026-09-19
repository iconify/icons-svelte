<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jas0kjbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jas0kjbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:googleappscript" {...props}></Icon>
