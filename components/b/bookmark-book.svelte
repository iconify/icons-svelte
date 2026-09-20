<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/i/ibr5ixl_o.css';
import '../../css/d/do1ou9w3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="ibr5ixl_o"/><path class="do1ou9w3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:bookmark-book" {...props}></Icon>
