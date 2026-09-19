<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esv2aeb_b.css';
import '../../css/g/g0ixy-bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esv2aeb_b"/><path class="g0ixy-bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:object-group" {...props}></Icon>
