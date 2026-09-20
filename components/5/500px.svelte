<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3byyvbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h3byyvbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:500px" {...props}></Icon>
