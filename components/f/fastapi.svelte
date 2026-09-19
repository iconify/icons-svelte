<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck9crekhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ck9crekhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:fastapi" {...props}></Icon>
