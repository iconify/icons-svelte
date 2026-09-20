<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esbhv0bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="esbhv0bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:112" {...props}></Icon>
