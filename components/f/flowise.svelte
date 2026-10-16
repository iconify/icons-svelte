<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6a8c-fpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216.75,"height":91.5};
const content = `<path class="g6a8c-fpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flowise" {...props}></Icon>
