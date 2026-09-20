<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f00xnhb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="f00xnhb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-down" {...props}></Icon>
