<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv4s0n6-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hv4s0n6-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cloud-arrow-down" {...props}></Icon>
