<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1fe2wnqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":168};
const content = `<path class="h1fe2wnqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloudinary" {...props}></Icon>
