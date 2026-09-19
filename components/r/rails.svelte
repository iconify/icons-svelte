<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok4pix9fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ok4pix9fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:rails" {...props}></Icon>
