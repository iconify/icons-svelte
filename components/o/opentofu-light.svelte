<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0yvy6unj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0yvy6unj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentofu-light" {...props}></Icon>
