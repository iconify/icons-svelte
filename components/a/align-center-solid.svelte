<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i31-vfb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i31-vfb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:align-center-solid" {...props}></Icon>
