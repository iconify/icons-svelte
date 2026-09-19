<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ng4k_tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="d0ng4k_tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:resize-full-circle" {...props}></Icon>
