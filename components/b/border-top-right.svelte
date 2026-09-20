<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylax2cbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ylax2cbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-top-right" {...props}></Icon>
