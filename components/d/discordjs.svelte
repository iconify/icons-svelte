<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml3okhbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ml3okhbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:discordjs" {...props}></Icon>
