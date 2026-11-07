<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx_bkof7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hx_bkof7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:hermes" {...props}></Icon>
