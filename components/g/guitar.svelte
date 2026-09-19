<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7fvj6z2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s7fvj6z2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:guitar" {...props}></Icon>
