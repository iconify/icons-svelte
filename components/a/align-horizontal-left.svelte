<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_a1hrbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z_a1hrbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:align-horizontal-left" {...props}></Icon>
