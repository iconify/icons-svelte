<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm4c2pb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sm4c2pb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-switch" {...props}></Icon>
