<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbpxjcbvi.css';
import '../../css/g/gpd_jwbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zbpxjcbvi"/><path class="gpd_jwbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:blender" {...props}></Icon>
