<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn599lbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pn599lbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:centos" {...props}></Icon>
