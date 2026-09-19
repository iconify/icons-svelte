<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2fhesbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2fhesbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-vertical" {...props}></Icon>
