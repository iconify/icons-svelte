<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggr-kcw4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ggr-kcw4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:donut-solid" {...props}></Icon>
