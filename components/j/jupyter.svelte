<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d66--gnqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d66--gnqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jupyter" {...props}></Icon>
