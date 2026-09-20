<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl42bbbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jl42bbbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-left-up" {...props}></Icon>
