<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh1vh8bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rh1vh8bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:business-progress-bar-2-solid" {...props}></Icon>
