<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqrud2bhn.css';
import '../../css/u/u_h_b-bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<rect class="wqrud2bhn"/><path class="u_h_b-bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:facebook" {...props}></Icon>
