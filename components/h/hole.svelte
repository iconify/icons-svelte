<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njswg3bpu.css';
import '../../css/v/v_g5t0bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="njswg3bpu"/><path class="v_g5t0bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hole" {...props}></Icon>
