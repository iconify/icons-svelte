<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0z26jaug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":68.505,"height":45.064};
const content = `<path class="z0z26jaug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kopia-dark" {...props}></Icon>
