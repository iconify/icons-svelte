<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaq5sebcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="oaq5sebcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:launch" {...props}></Icon>
