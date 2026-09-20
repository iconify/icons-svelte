<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1adf7z0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f1adf7z0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dataspell" {...props}></Icon>
