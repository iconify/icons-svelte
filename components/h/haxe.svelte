<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq1vsp_9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gq1vsp_9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:haxe" {...props}></Icon>
