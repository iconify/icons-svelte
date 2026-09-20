<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t05wrwc2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="t05wrwc2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-cursor-solid" {...props}></Icon>
