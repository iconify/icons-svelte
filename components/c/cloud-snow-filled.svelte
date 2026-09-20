<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqmw2l6ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uqmw2l6ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-snow-filled" {...props}></Icon>
