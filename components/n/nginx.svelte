<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqutpcb2e.css';
import '../../css/i/itzswk0_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xqutpcb2e"/><path class="itzswk0_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nginx" {...props}></Icon>
