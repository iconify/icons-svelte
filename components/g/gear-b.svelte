<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vva8lq2qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vva8lq2qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:gear-b" {...props}></Icon>
