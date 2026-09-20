<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fas5gactp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fas5gactp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:devicon" {...props}></Icon>
