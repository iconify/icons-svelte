<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy0cxlbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uy0cxlbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bookmark-sharp" {...props}></Icon>
