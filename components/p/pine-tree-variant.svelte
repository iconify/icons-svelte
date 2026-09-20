<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aif56fbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aif56fbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pine-tree-variant" {...props}></Icon>
