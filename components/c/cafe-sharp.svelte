<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le5ix3lon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="le5ix3lon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cafe-sharp" {...props}></Icon>
