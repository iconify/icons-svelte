<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxked7lst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":310,"height":512};
const content = `<path class="vxked7lst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mocha" {...props}></Icon>
