<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrm63qbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nrm63qbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:help-buoy" {...props}></Icon>
