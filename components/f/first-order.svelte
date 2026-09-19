<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngi88-baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ngi88-baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:first-order" {...props}></Icon>
