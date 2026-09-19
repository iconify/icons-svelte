<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s85i_fbsw.css';
import '../../css/o/ov9g6-b6k.css';
import '../../css/e/eww8hdbpb.css';
import '../../css/l/lbhftjbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s85i_fbsw"/><path class="ov9g6-b6k"/><path class="eww8hdbpb"/><path class="lbhftjbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cmake" {...props}></Icon>
