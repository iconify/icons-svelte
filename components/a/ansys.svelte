<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5woho7hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s5woho7hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ansys" {...props}></Icon>
