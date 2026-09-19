<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv-6a06tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bv-6a06tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pie-double" {...props}></Icon>
