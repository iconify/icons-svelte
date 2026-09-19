<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pet5d9ycq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pet5d9ycq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:renpy" {...props}></Icon>
