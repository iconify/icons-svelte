<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1nh42b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1nh42b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:medical-cross" {...props}></Icon>
