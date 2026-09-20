<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyv7au0jr.css';
import '../../css/x/xn30xyltc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hyv7au0jr"/><path clip-rule="evenodd" class="xn30xyltc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:linux-solid" {...props}></Icon>
