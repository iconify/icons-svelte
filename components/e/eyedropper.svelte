<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw3oh1bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zw3oh1bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:eyedropper" {...props}></Icon>
