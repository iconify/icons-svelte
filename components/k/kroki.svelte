<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopd9rgyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":279.728,"height":95.711};
const content = `<path class="gopd9rgyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kroki" {...props}></Icon>
