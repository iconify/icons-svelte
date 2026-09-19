<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elfvk3b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="elfvk3b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:l-square" {...props}></Icon>
