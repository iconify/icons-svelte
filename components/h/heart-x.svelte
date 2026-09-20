<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um1hfs5ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um1hfs5ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heart-x" {...props}></Icon>
