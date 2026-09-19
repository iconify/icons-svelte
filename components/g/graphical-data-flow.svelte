<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v451miqbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v451miqbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:graphical-data-flow" {...props}></Icon>
