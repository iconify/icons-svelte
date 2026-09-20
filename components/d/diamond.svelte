<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9lco3atb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j9lco3atb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:diamond" {...props}></Icon>
