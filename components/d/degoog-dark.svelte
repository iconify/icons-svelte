<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnm7m2cva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qnm7m2cva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:degoog-dark" {...props}></Icon>
