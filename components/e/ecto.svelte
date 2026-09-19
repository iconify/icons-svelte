<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7vdw0i-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f7vdw0i-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ecto" {...props}></Icon>
