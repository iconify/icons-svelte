<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-jz8wb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x-jz8wb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jeet" {...props}></Icon>
