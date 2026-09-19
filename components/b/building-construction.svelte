<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv4old3dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hv4old3dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:building-construction" {...props}></Icon>
