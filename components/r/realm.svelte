<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a36d3kanx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a36d3kanx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:realm" {...props}></Icon>
