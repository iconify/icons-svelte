<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2qdf5ous.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h2qdf5ous"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:idris" {...props}></Icon>
