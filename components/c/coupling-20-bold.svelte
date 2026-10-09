<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iplcxaclv.css';
import '../../css/o/oqts9w9jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iplcxaclv"/><path class="oqts9w9jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupling-20-bold" {...props}></Icon>
