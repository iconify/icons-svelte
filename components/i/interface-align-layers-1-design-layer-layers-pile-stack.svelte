<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3xbb8-vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c3xbb8-vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-align-layers-1-design-layer-layers-pile-stack" {...props}></Icon>
