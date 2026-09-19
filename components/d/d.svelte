<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypm8ffb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ypm8ffb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:d" {...props}></Icon>
