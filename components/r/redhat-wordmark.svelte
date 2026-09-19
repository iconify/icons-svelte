<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msuw89b-f.css';
import '../../css/n/nuybhrmtf.css';
import '../../css/s/sd9djh1wk.css';
import '../../css/h/h6rk2k5xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="msuw89b-f"/><path class="nuybhrmtf"/><path class="sd9djh1wk"/><path class="h6rk2k5xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:redhat-wordmark" {...props}></Icon>
