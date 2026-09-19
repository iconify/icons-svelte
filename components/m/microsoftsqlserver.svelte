<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc6f8x_ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vc6f8x_ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:microsoftsqlserver" {...props}></Icon>
