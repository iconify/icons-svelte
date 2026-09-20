<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxmoo7dca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxmoo7dca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:point-up-filled" {...props}></Icon>
