<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmv2sccxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mmv2sccxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:help" {...props}></Icon>
