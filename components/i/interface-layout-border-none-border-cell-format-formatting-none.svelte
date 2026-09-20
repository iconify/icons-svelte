<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9y5u9bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d9y5u9bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-layout-border-none-border-cell-format-formatting-none" {...props}></Icon>
