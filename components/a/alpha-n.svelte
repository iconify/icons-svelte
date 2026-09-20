<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-9b11ecn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="x-9b11ecn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-n" {...props}></Icon>
