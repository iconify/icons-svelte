<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4oh4_byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="s4oh4_byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud-upload" {...props}></Icon>
