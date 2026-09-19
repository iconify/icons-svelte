<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxvv67rcf.css';
import '../../css/g/glsd4_26w.css';
import '../../css/i/ifus-gbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hxvv67rcf"/><path class="glsd4_26w"/><path class="ifus-gbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:love2d" {...props}></Icon>
