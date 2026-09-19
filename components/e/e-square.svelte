<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8mm0wtyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="i8mm0wtyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:e-square" {...props}></Icon>
