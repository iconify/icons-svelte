<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx1qx3tfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qx1qx3tfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-p" {...props}></Icon>
