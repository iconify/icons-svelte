<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_u3a2y6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r_u3a2y6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-layout-border-bottom-border-bottom-cell-format-formatting" {...props}></Icon>
