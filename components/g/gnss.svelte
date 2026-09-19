<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnde1pb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fnde1pb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:gnss" {...props}></Icon>
