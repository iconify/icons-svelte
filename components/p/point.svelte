<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f98zace8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f98zace8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:point" {...props}></Icon>
