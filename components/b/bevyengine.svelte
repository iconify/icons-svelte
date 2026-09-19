<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-vwe2b6w.css';
import '../../css/f/fzp2tmx2o.css';
import '../../css/a/a6-7rqb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e-vwe2b6w"/><path class="fzp2tmx2o"/><path class="a6-7rqb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:bevyengine" {...props}></Icon>
