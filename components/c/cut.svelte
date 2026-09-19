<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp052t5vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dp052t5vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cut" {...props}></Icon>
