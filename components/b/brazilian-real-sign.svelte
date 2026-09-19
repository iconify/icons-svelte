<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oueemn-9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oueemn-9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:brazilian-real-sign" {...props}></Icon>
