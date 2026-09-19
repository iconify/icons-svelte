<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e649nyioo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e649nyioo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:contao" {...props}></Icon>
