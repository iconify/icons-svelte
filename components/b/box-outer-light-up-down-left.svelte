<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njeypru3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="njeypru3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-down-left" {...props}></Icon>
