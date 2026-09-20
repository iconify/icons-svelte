<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r75t4zbjb.css';
import '../../css/z/zh1f6hv8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="r75t4zbjb"/><path clip-rule="evenodd" class="zh1f6hv8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:round-cap-flat" {...props}></Icon>
