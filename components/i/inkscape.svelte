<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5l_z9buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b5l_z9buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:inkscape" {...props}></Icon>
